<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aey08u7-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aey08u7-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-libra-solid" /></template>
