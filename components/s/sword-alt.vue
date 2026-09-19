<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x77rc-kex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x77rc-kex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sword-alt" /></template>
