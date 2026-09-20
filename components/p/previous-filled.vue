<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfk15yb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfk15yb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:previous-filled" /></template>
