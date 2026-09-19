<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrkl4_7zf.css';
import '../../css/p/pc8rfjy_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="zrkl4_7zf"/><path class="pc8rfjy_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:nodejs" /></template>
