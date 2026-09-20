<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5y2qnprl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y5y2qnprl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-full-screen-circle-outline" /></template>
