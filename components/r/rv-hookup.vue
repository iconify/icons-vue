<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs9-0pbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rv-hookup" /></template>
<style>
.bs9-0pbcy {
  fill: currentColor;
  d: path("m19.346 20.308l-.707-.708l1.6-1.6H11.26q-.145.88-.834 1.44q-.688.56-1.58.56t-1.569-.56T6.431 18H5.346q-1.038 0-1.769-.73t-.73-1.77v-5h5.46v-3h-5.46v-1H14.23q.69 0 1.153.463t.462 1.153V17h4.381l-1.588-1.588l.707-.72l2.808 2.808zM9.385 10.5h5.461V8.116q0-.231-.192-.424T14.23 7.5H9.385zm.52 8.059q.441-.442.441-1.059t-.441-1.059T8.846 16t-1.058.441t-.442 1.059t.442 1.059q.44.441 1.058.441t1.059-.441");
}

</style>
