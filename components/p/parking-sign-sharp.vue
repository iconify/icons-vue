<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7i0ie9mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:parking-sign-sharp" /></template>
<style>
.k7i0ie9mz {
  fill: currentColor;
  d: path("M15.289 10.539h.884V8.846h3.154V5.462h-4.039zm.884-2.577V6.346h2.27v1.616zM12 13V3h10v10h-4.5v7h-1v-7zm-2.942 7v-2H3v-6.846h5.873L7.4 7H3V6h5.127l2.161 6.154V20zM6.87 15.692q.467 0 .789-.326q.322-.327.322-.793q0-.467-.327-.79q-.326-.321-.793-.321t-.789.326t-.322.793t.327.79q.326.321.793.321");
}

</style>
