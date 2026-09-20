<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r39ezvbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r39ezvbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-logo" /></template>
