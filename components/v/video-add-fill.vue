<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8rz1acbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8rz1acbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:video-add-fill" /></template>
