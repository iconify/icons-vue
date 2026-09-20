<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnz6y9byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnz6y9byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:quote-right-solid" /></template>
