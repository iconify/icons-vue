<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld2zemtmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld2zemtmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:rain-heavy" /></template>
