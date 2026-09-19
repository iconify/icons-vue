<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfutznb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfutznb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:snapchat" /></template>
