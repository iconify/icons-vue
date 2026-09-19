<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nke7y8bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nke7y8bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:youtube-solid" /></template>
