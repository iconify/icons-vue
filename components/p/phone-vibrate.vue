<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew60p602y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew60p602y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:phone-vibrate" /></template>
