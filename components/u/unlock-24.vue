<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpqhu_r9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpqhu_r9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unlock-24" /></template>
