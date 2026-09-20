<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm95__uzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm95__uzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:rice-filled" /></template>
