<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aunntjnhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aunntjnhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:voice-recognition-fill" /></template>
