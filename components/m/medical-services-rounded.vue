<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0ne68sla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:medical-services-rounded" /></template>
<style>
.i0ne68sla {
  fill: currentColor;
  d: path("M4.616 21q-.691 0-1.153-.462T3 19.385V8.615q0-.69.463-1.152T4.615 7H9V5.615q0-.69.463-1.153T10.616 4h2.769q.69 0 1.153.462T15 5.615V7h4.385q.69 0 1.152.463T21 8.616v10.769q0 .69-.463 1.153T19.385 21zM10 7h4V5.615q0-.23-.192-.423T13.385 5h-2.77q-.23 0-.423.192T10 5.615zm1.5 7.5V17q0 .214.143.357T12 17.5t.357-.143T12.5 17v-2.5H15q.214 0 .357-.143T15.5 14t-.143-.357T15 13.5h-2.5V11q0-.213-.143-.357T12 10.5t-.357.143T11.5 11v2.5H9q-.213 0-.357.143T8.5 14t.143.357T9 14.5z");
}

</style>
