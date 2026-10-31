<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmqyipb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmqyipb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sparkle-round" /></template>
