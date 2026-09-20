<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldyatl2-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldyatl2-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:tumblr-logo" /></template>
