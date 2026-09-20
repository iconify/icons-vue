<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm7smsbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-ethernet-outline-sharp" /></template>
<style>
.wm7smsbjc {
  fill: currentColor;
  d: path("M16.308 17.308L15.6 16.6l4.589-4.6L15.6 7.4l.708-.708L21.616 12zm-8.616 0L2.385 12l5.307-5.308l.708.708L3.812 12L8.4 16.6zm-.241-4.76q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.221.547t-.55.22t-.547-.221m4 0q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.221.547t-.55.22t-.547-.221m4 0q-.22-.222-.22-.55t.221-.547t.55-.22t.547.221t.22.55t-.221.547t-.55.22t-.547-.221");
}

</style>
