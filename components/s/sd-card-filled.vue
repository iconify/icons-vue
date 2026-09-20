<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vslx7zj_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vslx7zj_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sd-card-filled" /></template>
