<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw4qccbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw4qccbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:upload" /></template>
