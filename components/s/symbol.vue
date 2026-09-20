<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_7v7zfgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_7v7zfgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:symbol" /></template>
