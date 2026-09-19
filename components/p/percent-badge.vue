<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnhq3rbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnhq3rbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:percent-badge" /></template>
