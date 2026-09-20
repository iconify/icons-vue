<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b430c0b3m.css';
import '../../css/t/tvql3c4ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b430c0b3m"/><path class="tvql3c4ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moderate-snow-fill" /></template>
