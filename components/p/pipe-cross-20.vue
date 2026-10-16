<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm-ms1i2h.css';
import '../../css/x/xe4qnpbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hm-ms1i2h"/><path class="xe4qnpbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-cross-20" /></template>
