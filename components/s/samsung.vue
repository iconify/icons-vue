<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upbew9bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upbew9bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:samsung" /></template>
