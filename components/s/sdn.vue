<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i0dv3xwkh"/><path class="xmw2sf50r"/><path class="yqzg_6biy"/><path class="l2brf2ydb"/><path class="aio5znovg"/><path class="rp29pc0az"/><path class="ihxs92b4t"/><path class="nc0yovb5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sdn" /></template>
<style>
.aio5znovg {
  fill: var(--svg-color--592bb0, #592bb0);
  d: path("M5.745 17.486c8.97-1.86 9.485-5.475 8.615-7.05c.52 1.24-.37 4.215-8.105 6.22z");
}

.ft5dv1b6b {
  fill: none;
}

.i0dv3xwkh {
  fill: var(--svg-color--592bb0, #592bb0);
  d: path("M18.255 6.516c-8.97 1.86-9.485 5.475-8.615 7.05c-.52-1.24.37-4.215 8.105-6.22z");
}

.ihxs92b4t {
  fill: var(--svg-color--bca1e6, #bca1e6);
  d: path("M16.35 16.255c1.76-2.71-.62-5.275-2.03-6.215c2.185 2.71 2.615 4.75.645 6.64c-1.97 1.9-5.34 3.245-8.35 3.735L7.62 21c2.18-.45 6.98-2.03 8.735-4.745z");
}

.l2brf2ydb {
  fill: var(--svg-color--804fc5, #804fc5);
  d: path("M17.73 3.9c-1.05.104-3.915.79-6.95 2.66c-2.985 1.844-2.995 4.014-2.615 4.914c-.035-.66.475-2.4 2.79-4.1s6.02-2.585 7.58-2.815l-.8-.66z");
}

.nc0yovb5a {
  fill: var(--svg-color--804fc5, #804fc5);
  d: path("M6.27 20.1c1.05-.105 3.916-.79 6.95-2.66c2.986-1.845 2.996-4.015 2.616-4.915c.035.66-.475 2.4-2.79 4.1s-6.02 2.585-7.58 2.815l.8.66z");
}

.rp29pc0az {
  fill: var(--svg-color--734bbb, #734bbb);
  d: path("M14.7 14.439c1.03-1.59.635-2.7.31-3.065c.52 3.94-6.125 6.1-9.515 6.68L5 19.039c3.14-.37 8.42-2.615 9.7-4.6");
}

.xmw2sf50r {
  fill: var(--svg-color--734bbb, #734bbb);
  d: path("M9.3 9.56c-1.03 1.59-.635 2.7-.31 3.065c-.52-3.94 6.125-6.1 9.515-6.68L19 4.96c-3.14.37-8.42 2.615-9.7 4.6");
}

.yqzg_6biy {
  fill: var(--svg-color--bca1e6, #bca1e6);
  d: path("M7.65 7.745c-1.76 2.71.62 5.275 2.03 6.215c-2.185-2.71-2.615-4.75-.646-6.64c1.97-1.9 5.34-3.245 8.35-3.735L16.38 3c-2.18.45-6.98 2.03-8.735 4.745z");
}

</style>
