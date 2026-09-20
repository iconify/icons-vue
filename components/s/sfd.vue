<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGwnbK6buM)" class="ii_gz2b9i"/><path fill="url(#SVGlPegTMjk)" class="d51o-mb1e"/><path fill="url(#SVGl9AKGecC)" class="s8-6ycdwl"/><path class="fts9vpqzg"/><path class="y4qwd-b-f"/><path clip-rule="evenodd" class="g1lqlbhzd"/><defs><linearGradient id="SVGwnbK6buM" x1="11.929" x2="11.929" y1="3" y2="21.006" gradientUnits="userSpaceOnUse"><stop class="xstq87bsk"/><stop offset="1" class="af0d7lbhm"/></linearGradient><linearGradient id="SVGlPegTMjk" x1="12.071" x2="12.071" y1="3" y2="21.006" gradientUnits="userSpaceOnUse"><stop class="bj7taeb_z"/><stop offset="1" class="rq6nn5bry"/></linearGradient><linearGradient id="SVGl9AKGecC" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="i1hj57bcq"/><stop offset="1" class="d4wyeeo_u"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sfd" /></template>
<style>
.af0d7lbhm {
  stop-color: var(--svg-color--126db0, #126db0);
}

.bj7taeb_z {
  stop-color: var(--svg-color--1aa3cb, #1aa3cb);
}

.d4wyeeo_u {
  stop-color: var(--svg-color--0e59ab, #0e59ab);
}

.d51o-mb1e {
  d: path("m12.474 3l1.15 1.587v.53c1.517.427 4.42 1.943 5.685 2.648c0 1.483-.54 5.206-.815 6.883l.275.265l.81 1.848l-2.435-1.582c.65-1.696.63-5.296.54-6.883c-1.298-1.061-4.036-1.857-5.21-2.118z");
}

.ft5dv1b6b {
  fill: none;
}

.fts9vpqzg {
  fill: var(--svg-color--303435, #303435);
  d: path("M12.056 5.843c-2.027 0-5.064 1.075-5.907 2.155C4.572 15.758 9.37 19.187 12 19.817c6.187-1.616 6.523-8.048 5.964-11.819c-1.132-1.35-3.884-2.155-5.907-2.155");
}

.g1lqlbhzd {
  fill: var(--svg-color--949398, #949398);
  fill-rule: evenodd;
  d: path("M12.474 6.79v11.842c1.099-.426 3.458-1.852 4.12-4.121c.507-1.93.692-3.93.55-5.921a9.6 9.6 0 0 0-4.67-1.8m.947 1.42v8.527c1.056-.663 3.098-3.126 2.814-7.674c-.583-.284-1.97-.852-2.814-.852");
}

.i1hj57bcq {
  stop-color: var(--svg-color--1868a7, #1868a7);
}

.ii_gz2b9i {
  d: path("m11.526 3l-1.15 1.587v.53c-1.517.427-4.42 1.943-5.685 2.648c0 1.483.54 5.206.815 6.883l-.275.265l-.81 1.848l2.435-1.582c-.65-1.696-.63-5.296-.54-6.883c1.298-1.061 4.036-1.857 5.21-2.118z");
}

.rq6nn5bry {
  stop-color: var(--svg-color--126db1, #126db1);
}

.s8-6ycdwl {
  d: path("m7.4 15.97l-2.71 1.59l2.166.261l.27-.26C8.21 19.247 10.826 20.559 12 21c2.6-1.061 4.33-2.733 4.874-3.44l.27.261l2.165-.26l-2.71-1.592c-.862 1.91-3.424 3.269-4.6 3.71c-2.382-.64-4.059-2.739-4.599-3.71");
}

.xstq87bsk {
  stop-color: var(--svg-color--1ba9d1, #1ba9d1);
}

.y4qwd-b-f {
  fill: var(--svg-color--cacad4, #cacad4);
  d: path("M10.579 10.139c.644-.209.857-.261.947-.261V6.79c-1.501.203-3.661 1.288-4.557 1.8c-.426 1.032 0 3.694.27 4.893c.645-.412 2.535-1.028 3.34-1.289v4.121c-1.07-.208-2-1.8-2.27-2.576l-1.07.52c.645 2.672 3.127 4.027 4.287 4.373V10.65c-1.288 0-2.78.616-3.316.876V9.632l2.37-1.042z");
}

</style>
