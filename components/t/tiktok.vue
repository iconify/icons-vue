<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiw05rb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiw05rb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tiktok" /></template>
