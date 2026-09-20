<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhrm0qbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhrm0qbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-error-1-filled" /></template>
