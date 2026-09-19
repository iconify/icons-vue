<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5t9p-b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5t9p-b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:text-align-right" /></template>
