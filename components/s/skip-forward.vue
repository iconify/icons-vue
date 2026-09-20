<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x254e0blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x254e0blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:skip-forward" /></template>
