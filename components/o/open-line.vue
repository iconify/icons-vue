<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho73_5byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho73_5byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:open-line" /></template>
