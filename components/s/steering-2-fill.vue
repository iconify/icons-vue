<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6kj7gj9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6kj7gj9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:steering-2-fill" /></template>
