<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cshcm0g2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cshcm0g2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:ubuntu" /></template>
