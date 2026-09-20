<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1a27zb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1a27zb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:star-off" /></template>
