<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="q6ogy2blb"/><g class="ablnaeb2e"><path class="zzedyub4v"/><path class="bxgdq9bmt"/></g><g class="buq4ssbjv"><ellipse class="k4v94kxjb"/><path class="ij-5jxaug"/><path class="or7t4kuam"/></g><path class="px3--75-t"/><path class="f15a53lvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:tropical-drink" /></template>
<style>
.ablnaeb2e {
  fill: var(--svg-color--e9b93b, #e9b93b);
}

.buq4ssbjv {
  fill: var(--svg-color--bac4c9, #bac4c9);
  fill-opacity: var(--svg-fill-opacity--0-627, 0.627);
}

.bxgdq9bmt {
  d: path("M39.987 10.439c-.368.17-.726.368-1.061.586l-.335.218l.339.182c.438.237.874.51 1.304.81l.147.102l.16-.1c.254-.163.52-.308.79-.435c3.929-1.847 8.901.072 11.08 4.274c.335.649.591 1.324.765 2.01c.939 3.749-.675 7.435-3.929 8.962q-.27.125-.553.231l.004-.012l-.337.055l-.243.034l-.008.209c0 .1-.007.2-.011.297l-.02.118l.012-.002q-.032.47-.096.914l-.052.365l.386-.118c.388-.124.77-.271 1.137-.443c3.94-1.852 5.908-6.291 4.778-10.79a11 11 0 0 0-.905-2.389c-2.614-5.04-8.606-7.315-13.356-5.082");
}

.f15a53lvd {
  fill: var(--svg-color--da1c5c, #da1c5c);
  d: path("M47.46 17.637c0 14.637-7.387 26.503-16.5 26.503c-9.115 0-16.499-11.866-16.499-26.503");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.ij-5jxaug {
  d: path("M32.79 60.16c0 .516-.818.934-1.832.934c-1.01 0-1.831-.418-1.831-.934V42.12c0-.514.823-.933 1.831-.933c1.014 0 1.832.419 1.832.933z");
  opacity: var(--svg-opacity--0-67, 0.67);
}

.k4v94kxjb {
  cx: 30.959px;
  cy: 61.1px;
  opacity: var(--svg-opacity--0-67, 0.67);
  rx: 10.786px;
  ry: 2.904px;
}

.or7t4kuam {
  d: path("M52.1 15.494c0 17.199-9.462 31.14-21.14 31.14c-11.675 0-21.14-13.94-21.14-31.14");
  opacity: var(--svg-opacity--0-67, 0.67);
}

.px3--75-t {
  fill: var(--svg-color--068777, #068777);
  d: path("M52.05-.205C45.677 0 39.452 2.552 36.214 8.786c-2.276 4.379-3.107 9.493-4.383 14.25c-1.438 5.348-2.665 10.642-3.542 16.12c-.392 2.438 3.195 2.828 3.585.392c1.415-8.801 3.588-17.74 6.283-26.23c2.183-6.886 8.02-9.535 14.377-9.742c2.328-.074 1.816-3.855-.484-3.778");
}

.q6ogy2blb {
  fill: var(--svg-color--e79524, #e79524);
  d: path("M48.605 28.363s-.142-9.562-9.488-17.213l4.791-.841l2.76.645l3.248 1.219l2.512 2.614l.613 2.307l1 2.738l-.259 2.83l-1.2 2.894l-1.635 2.207l-2.344.6");
}

.zzedyub4v {
  d: path("M47.27 23.1s-.705-4.04-4.02-7.414l1.372-.28l.868.316l1.057.564l.931 1.147l.343.979l.49 1.174l.116 1.189l-.159 1.202l-.335.908l-.659.215");
}

</style>
