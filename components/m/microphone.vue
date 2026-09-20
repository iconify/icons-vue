<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8q-aybpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="u8q-aybpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:microphone" /></template>
