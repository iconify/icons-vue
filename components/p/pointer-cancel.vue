<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i33b-_9mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i33b-_9mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-cancel" /></template>
