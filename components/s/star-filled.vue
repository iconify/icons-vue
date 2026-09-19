<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tetjp7m-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tetjp7m-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:star-filled" /></template>
