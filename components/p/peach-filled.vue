<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp2g-og5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp2g-og5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:peach-filled" /></template>
