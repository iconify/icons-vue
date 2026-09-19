<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgzi0ccar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bgzi0ccar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:speech-balloon" /></template>
