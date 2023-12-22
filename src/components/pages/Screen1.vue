<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="f561f943-9539-4969-a1f1-d09dfbeda408"
    v-bind:style="{'width':'100%','height':'auto'}">
    <WButton tag="button" href="" v-bind:pill="false" size="md" text="Button" type="button" v-bind:block="false"
      color="#FFFFFF" v-bind:snapX="false" v-bind:snapY="false" theme="theme--light01" v-bind:rotate="0"
      v-bind:squared="false" variant="primary" ncBgType="bgColor" position="relative" v-bind:isEnabled="true"
      background="#007bff" linkTarget="_top" ncLinkType="link" borderColor="#007bff" v-bind:resetTrigger="false"
      animationName="" ncTooltipText="" verticalWidth="60px" formTransition="none"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
      verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" toForRouterLink="to"
      horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
      nucalScaleHeight="" ncClickBorderColor="#007BFF" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007BFF"
      ncHoverBorderColor="#007BFF" ncDisableBorderColor="transparent" ncClickBackgroundColor="#007BFF"
      ncFocusBackgroundColor="#007BFF" ncHoverBackgroundColor="#007BFF" ncDisableBackgroundColor="#969696"
      id="19a1ac58-11d3-4bfa-b564-e29d4dc2a0ef"
      v-bind:style="{'width':'100%','filter':'none','height':'100%','zIndex':2,'tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','textAlign':'center','fontFamily':'Open Sans','fontWeight':700,'lineHeight':'1.4','marginLeft':'','paddingTop':'','textIndent':'0px','textShadow':'','visibility':'visible','whiteSpace':'pre-wrap','borderStyle':'solid','marginRight':'','paddingLeft':'','wordSpacing':'0px','marginBottom':'','mixBlendMode':'normal','paddingRight':'','letterSpacing':'0px','paddingBottom':'','textTransform':'none','backdropFilter':'none','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
    <WButton tag="button" href="" v-bind:pill="false" size="md" text="Button" type="button" v-bind:block="false"
      color="#FFFFFF" v-bind:snapX="false" v-bind:snapY="false" theme="theme--light01" v-bind:rotate="0"
      v-bind:squared="false" variant="primary" ncBgType="bgColor" position="relative" v-bind:isEnabled="true"
      background="#007bff" linkTarget="_top" ncLinkType="link" borderColor="#007bff" v-bind:resetTrigger="false"
      animationName="" ncTooltipText="" verticalWidth="60px" formTransition="none"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
      verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" toForRouterLink="to"
      horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
      nucalScaleHeight="" ncClickBorderColor="#007BFF" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007BFF"
      ncHoverBorderColor="#007BFF" ncDisableBorderColor="transparent" ncClickBackgroundColor="#007BFF"
      ncFocusBackgroundColor="#007BFF" ncHoverBackgroundColor="#007BFF" ncDisableBackgroundColor="#969696"
      id="0c3cf6f7-56cb-4049-bb19-416740c478bb"
      v-bind:style="{'width':'100%','filter':'none','height':'100%','zIndex':3,'tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','textAlign':'center','fontFamily':'Open Sans','fontWeight':700,'lineHeight':'1.4','marginLeft':'','paddingTop':'','textIndent':'0px','textShadow':'','visibility':'visible','whiteSpace':'pre-wrap','borderStyle':'solid','marginRight':'','paddingLeft':'','wordSpacing':'0px','marginBottom':'','mixBlendMode':'normal','paddingRight':'','letterSpacing':'0px','paddingBottom':'','textTransform':'none','backdropFilter':'none','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
  </DropZone>
</template>
<script>
import { mapGetters } from 'vuex';
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: { ...mapGetters('source', ['getApiMappingWithChain'])},
  methods: {bindSource(chain) { return this.getApiMappingWithChain(chain); }},
  watch: {},
};
</script>

<style lang="scss" scoped>@import 'src/assets/styles/scroll';
 @include custom-scroll();
@media (min-width: 1024.05px){
[id='f561f943-9539-4969-a1f1-d09dfbeda408'] {
             display: grid; 
             grid-template-columns: 31.0546875rem 5.3125rem 28.4375rem 5.3125rem 29.8828125rem;
             grid-template-rows: minmax(31.25rem, max-content) minmax(2.421875rem, max-content) minmax(6.71875rem, max-content) minmax(2.421875rem, max-content) minmax(44.53125rem, max-content);
          }
[id='19a1ac58-11d3-4bfa-b564-e29d4dc2a0ef']{
          grid-area: 2/4/3/5;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          }
[id='0c3cf6f7-56cb-4049-bb19-416740c478bb']{
          grid-area: 4/2/5/3;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          }
}
@media (min-width: 768.05px) and (max-width: 1024px){
[id='f561f943-9539-4969-a1f1-d09dfbeda408'] {
             display: grid; 
             grid-template-columns: 46.6796875rem 0 6.640625rem 0 46.6796875rem;
             grid-template-rows: minmax(39.0625rem, max-content) minmax(3.02734375rem, max-content) minmax(8.3984375rem, max-content) minmax(3.02734375rem, max-content) minmax(3.125rem, max-content);
          }
[id='19a1ac58-11d3-4bfa-b564-e29d4dc2a0ef']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(12rem, 12px),1.171875rem);
          }
[id='0c3cf6f7-56cb-4049-bb19-416740c478bb']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),1.171875rem);
          }
}
@media (min-width: 480.05px) and (max-width: 768px){
[id='f561f943-9539-4969-a1f1-d09dfbeda408'] {
             display: grid; 
             grid-template-columns: 45.572916666666664rem 0 8.854166666666666rem 0 45.572916666666664rem;
             grid-template-rows: minmax(52.083333333333336rem, max-content) minmax(4.036458333333333rem, max-content) minmax(11.197916666666666rem, max-content) minmax(4.036458333333333rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='19a1ac58-11d3-4bfa-b564-e29d4dc2a0ef']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(12rem, 12px),1.5625rem);
          }
[id='0c3cf6f7-56cb-4049-bb19-416740c478bb']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),1.5625rem);
          }
}
@media (min-width: 375.05px) and (max-width: 480px){
[id='f561f943-9539-4969-a1f1-d09dfbeda408'] {
             display: grid; 
             grid-template-columns: 42.916666666666664rem 0 14.166666666666666rem 0 42.916666666666664rem;
             grid-template-rows: minmax(83.33333333333333rem, max-content) minmax(6.458333333333333rem, max-content) minmax(17.916666666666668rem, max-content) minmax(6.458333333333333rem, max-content) minmax(5rem, max-content);
          }
[id='19a1ac58-11d3-4bfa-b564-e29d4dc2a0ef']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(12rem, 12px),2.5rem);
          }
[id='0c3cf6f7-56cb-4049-bb19-416740c478bb']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),2.5rem);
          }
}
@media (min-width: 0px) and (max-width: 375px){
[id='f561f943-9539-4969-a1f1-d09dfbeda408'] {
             display: grid; 
             grid-template-columns: 6.4rem 0 87.20000000000002rem 0 6.4rem;
             grid-template-rows: minmax(106.66666666666667rem, max-content) minmax(39.7529411764706rem, max-content) minmax(22.933333333333334rem, max-content) minmax(39.7529411764706rem, max-content) minmax(6.4rem, max-content);
          }
[id='19a1ac58-11d3-4bfa-b564-e29d4dc2a0ef']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(12rem, 12px),15.38823529411765rem);
          }
[id='0c3cf6f7-56cb-4049-bb19-416740c478bb']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),15.38823529411765rem);
          }
}
</style>