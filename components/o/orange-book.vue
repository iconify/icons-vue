<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fk_qeccxi"/><path class="i2qup1gyz"/><path class="ladzczbyq"/><path class="njiuhcpbw"/><path class="frjk-thhm"/><path class="iih-muwov"/><path class="q_kp_kbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:orange-book" /></template>
<style>
.fk_qeccxi {
  fill: var(--svg-color--34484c, #34484c);
  d: path("M6.208 57.475s1.882 7.029 13.673 5.23l2-4.702l-3.391-3.575l-9.385-3.005l-2.899 6.052");
}

.frjk-thhm {
  fill: var(--svg-color--34484c, #34484c);
  d: path("M15.233 19.405c0-.723.134-1.299.391-1.79c-3.231-.294-6.284-1.2-8.51-3.145c-.741.66-1.105 1.478-1.105 2.699V55.96c0 2.49 2.088 4.509 4.654 4.509l4.593-1.879c-.001-.133-.022-.26-.022-.394z");
}

.i2qup1gyz {
  fill: var(--svg-color--ad7029, #ad7029);
  d: path("M43.767 44.306c0 2.488-1.318 3.144-4.652 4.507L10.652 60.471C8.082 60.47 6 58.453 6 55.962V17.17c0-2.493 1.512-3.322 4.652-4.512L39.114 1c2.572 0 4.652 2.023 4.652 4.512v38.794");
}

.iih-muwov {
  fill: var(--svg-color--f79420, #f79420);
  d: path("M53.819 48.127c0 2.491-1.322 3.145-4.651 4.51l-29.29 10.07c-2.57 0-4.656-2.019-4.656-4.51V19.405c0-2.49 1.512-3.318 4.656-4.514l29.29-10.067c2.567 0 4.651 2.02 4.651 4.512z");
}

.ladzczbyq {
  fill: var(--svg-color--34484c, #34484c);
  d: path("M8.586 59.995s10.667 2.968 11.294 2.711c.619-.254-.399-4.485-.399-4.485l-3.858-4.03l-3.596-.162l-.631.869z");
}

.njiuhcpbw {
  fill: var(--svg-color--f4f5f5, #f4f5f5);
  d: path("M38.447 3.687L6.869 16.553l1.481 8.243l4.699.458l15.69-2.449l9.752-4.958l7.18-9.534c-1.57-2.728-3.874-4.418-7.224-4.626");
}

.q_kp_kbgr {
  fill: var(--svg-color--905a24, #905a24);
  d: path("M41.691 16.663a.605.605 0 0 1-.362.79l-15.575 5.829a.64.64 0 0 1-.814-.35a.604.604 0 0 1 .36-.79l15.577-5.828a.64.64 0 0 1 .814.351m0 2.772a.605.605 0 0 1-.362.79l-15.575 5.819a.635.635 0 0 1-.814-.35a.604.604 0 0 1 .36-.785l15.577-5.829a.636.636 0 0 1 .814.35m-5.294 4.864c.125.316.049.637-.173.72l-10.637 3.979c-.222.08-.502-.107-.629-.42c-.124-.314-.045-.638.177-.722l10.637-3.977c.218-.08.499.106.625.42");
}

</style>
