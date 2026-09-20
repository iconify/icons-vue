<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9bfxnb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9bfxnb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-x-sharp-fill" /></template>
