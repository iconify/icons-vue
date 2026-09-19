<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebuhi1bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebuhi1bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vertical-align-center-filled" /></template>
