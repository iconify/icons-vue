<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egto-7bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egto-7bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:trimble" /></template>
