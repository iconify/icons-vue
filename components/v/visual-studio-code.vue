<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7t7plf6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7t7plf6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:visual-studio-code" /></template>
