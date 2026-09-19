<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2e24i0lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2e24i0lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:user-plus" /></template>
