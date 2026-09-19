<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teo9tmjwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":627};
const content = `<path class="teo9tmjwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:quote" /></template>
