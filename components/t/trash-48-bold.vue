<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcwfyf16x.css';
import '../../css/s/s5tz5x6dr.css';
import '../../css/u/ueeyhi2_o.css';
import '../../css/g/gwc7-sbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pcwfyf16x"/><path class="s5tz5x6dr"/><path class="ueeyhi2_o"/><path class="gwc7-sbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trash-48-bold" /></template>
