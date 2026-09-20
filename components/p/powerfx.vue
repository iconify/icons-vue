<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am883v--m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am883v--m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:powerfx" /></template>
