<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9lqumu8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9lqumu8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-filled" /></template>
