<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrh--nbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrh--nbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-check-round" /></template>
