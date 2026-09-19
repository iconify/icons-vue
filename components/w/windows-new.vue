<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfh-c-blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfh-c-blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:windows-new" /></template>
