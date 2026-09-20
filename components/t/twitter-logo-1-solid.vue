<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwnocrufn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwnocrufn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:twitter-logo-1-solid" /></template>
