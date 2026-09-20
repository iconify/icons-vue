<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aomeu167z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aomeu167z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-square-fill" /></template>
