<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir5c0ly1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir5c0ly1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:microsoft" /></template>
