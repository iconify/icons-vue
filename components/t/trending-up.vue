<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qilqr3leb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qilqr3leb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:trending-up" /></template>
