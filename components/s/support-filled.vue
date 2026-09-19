<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5e579eoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5e579eoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:support-filled" /></template>
