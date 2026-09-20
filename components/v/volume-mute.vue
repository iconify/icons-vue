<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eripg9b9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eripg9b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:volume-mute" /></template>
