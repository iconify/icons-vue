<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6odt7b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6odt7b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pen-alt" /></template>
