<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amw5bjb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:missed-video-call" /></template>
<style>
.amw5bjb7t {
  fill: currentColor;
  d: path("m11.22 15.308l3.807-3.858l-.708-.708l-3.1 3.139l-3.43-3.42h2.269v-1h-4v4h1v-2.315zM5.095 19q-.69 0-1.153-.462t-.462-1.153V6.615q0-.69.462-1.152T5.096 5h10.77q.69 0 1.152.463t.463 1.153v4.653l3.038-3.038v7.538l-3.038-3.038v4.654q0 .69-.463 1.153T15.866 19z");
}

</style>
