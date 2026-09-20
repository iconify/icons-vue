<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsi7ipshf.css';
import '../../css/p/p3hf5o7_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="fsi7ipshf"/><path clip-rule="evenodd" class="p3hf5o7_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:shield-dollar" /></template>
