<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgx1k0bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgx1k0bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:microphone-fill" /></template>
