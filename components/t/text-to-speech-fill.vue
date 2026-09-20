<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bei3qrbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bei3qrbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:text-to-speech-fill" /></template>
