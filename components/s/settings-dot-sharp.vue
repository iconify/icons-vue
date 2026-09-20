<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvtn-kbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvtn-kbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:settings-dot-sharp" /></template>
