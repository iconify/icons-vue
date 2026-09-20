<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi3uknbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fi3uknbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notebook-outline" /></template>
