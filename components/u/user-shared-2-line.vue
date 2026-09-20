<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it8quy38i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it8quy38i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-shared-2-line" /></template>
