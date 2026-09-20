<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9w3hdc5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9w3hdc5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:signal-4g" /></template>
