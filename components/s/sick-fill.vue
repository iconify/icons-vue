<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy2kl1buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy2kl1buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sick-fill" /></template>
