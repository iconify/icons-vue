<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmxqd5bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmxqd5bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:mistral" /></template>
