<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo3hx7b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo3hx7b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tui" /></template>
