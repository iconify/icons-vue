<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyep25f0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyep25f0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sam-s-club" /></template>
