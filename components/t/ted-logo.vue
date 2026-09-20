<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7gb91bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7gb91bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:ted-logo" /></template>
