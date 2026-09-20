<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpb1l9bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rv-hookup-outline-sharp" /></template>
<style>
.wpb1l9bzk {
  fill: currentColor;
  d: path("m19.346 20.308l-.707-.708l1.6-1.6H11.26q-.145.88-.834 1.44q-.688.56-1.58.56t-1.569-.56T6.431 18H2.846v-7.5h5.462v-3H2.846v-1h13V17h4.381l-1.588-1.588l.707-.72l2.808 2.808zM9.385 10.5h5.461v-3H9.385zm.52 8.059q.441-.442.441-1.059t-.441-1.059T8.846 16t-1.058.441t-.442 1.059t.442 1.059q.44.441 1.058.441t1.059-.441M6.43 17q.171-.88.847-1.44T8.846 15t1.581.56q.689.56.835 1.44h3.584v-5.5h-11V17zm0-5.5H3.846h11z");
}

</style>
