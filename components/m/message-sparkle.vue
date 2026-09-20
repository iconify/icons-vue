<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m71ah9bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m71ah9bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-sparkle" /></template>
