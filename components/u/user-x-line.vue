<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc4mb0wfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc4mb0wfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-x-line" /></template>
