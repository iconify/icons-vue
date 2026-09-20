<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uag-hsb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uag-hsb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:map" /></template>
