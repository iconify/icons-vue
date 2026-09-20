<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9eirc5vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9eirc5vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:razor" /></template>
