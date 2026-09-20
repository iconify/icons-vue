<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv5td14oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv5td14oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-x" /></template>
