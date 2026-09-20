<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en1w-_b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en1w-_b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pill-off" /></template>
