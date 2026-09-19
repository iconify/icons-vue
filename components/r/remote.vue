<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fplqo9wyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fplqo9wyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:remote" /></template>
