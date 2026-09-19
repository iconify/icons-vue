<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_-i05dah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="g_-i05dah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-github" /></template>
