<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd110abrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd110abrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-plus-sharp" /></template>
