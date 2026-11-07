<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvskk7nlf.css';
import '../../css/d/d9yqzeb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvskk7nlf"/><path clip-rule="evenodd" class="d9yqzeb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-minimalistic-horizontal-bold" /></template>
