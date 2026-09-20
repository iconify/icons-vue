<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6ungdc8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6ungdc8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-check-fill" /></template>
