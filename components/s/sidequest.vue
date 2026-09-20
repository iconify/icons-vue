<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3rlx0bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3rlx0bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sidequest" /></template>
