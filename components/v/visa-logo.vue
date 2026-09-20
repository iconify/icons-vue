<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6w0w00-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6w0w00-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:visa-logo" /></template>
