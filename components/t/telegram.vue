<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd8mwpbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd8mwpbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:telegram" /></template>
