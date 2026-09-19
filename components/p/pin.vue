<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7ad1vxag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7ad1vxag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pin" /></template>
