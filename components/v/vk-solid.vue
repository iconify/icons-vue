<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/damz3ibbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="damz3ibbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:vk-solid" /></template>
