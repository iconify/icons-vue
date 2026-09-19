<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-7zdubzz.css';
import '../../css/j/jjj7yd_xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-7zdubzz"/><path class="jjj7yd_xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:software" /></template>
