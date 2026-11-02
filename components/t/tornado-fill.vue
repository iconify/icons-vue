<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8nghhbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8nghhbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tornado-fill" /></template>
