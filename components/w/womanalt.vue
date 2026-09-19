<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izzlobcjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":1024};
const content = `<path class="izzlobcjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:womanalt" /></template>
