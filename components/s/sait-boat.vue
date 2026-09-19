<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zssdm33po.css';
import '../../css/s/s_ch1sbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="zssdm33po"/><path class="s_ch1sbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:sait-boat" /></template>
