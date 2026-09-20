<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipku0rblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipku0rblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:shadcnui" /></template>
