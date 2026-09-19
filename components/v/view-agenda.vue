<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1kqg3xar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1kqg3xar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:view-agenda" /></template>
