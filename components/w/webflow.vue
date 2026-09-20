<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csd0tik1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csd0tik1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:webflow" /></template>
