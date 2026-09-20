<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ackwvkend.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ackwvkend"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-15-fill" /></template>
