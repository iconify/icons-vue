<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frerr6bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frerr6bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:view-360-number" /></template>
