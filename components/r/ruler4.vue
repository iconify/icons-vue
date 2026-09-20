<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbzc4ebog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbzc4ebog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ruler4" /></template>
