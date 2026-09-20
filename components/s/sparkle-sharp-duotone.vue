<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl5ni9bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl5ni9bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sparkle-sharp-duotone" /></template>
