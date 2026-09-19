<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix7dw7eey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ix7dw7eey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trigger-hurt" /></template>
