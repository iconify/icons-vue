<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu_817jpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zu_817jpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:user-exclamation-solid" /></template>
