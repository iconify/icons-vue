<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haetg-w3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haetg-w3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:sparkle" /></template>
