<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwsr-b07g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hwsr-b07g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-full-screen-outline" /></template>
