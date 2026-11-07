<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5e6tzbau.css';
import '../../css/l/lg5xwxuqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5e6tzbau"/><path clip-rule="evenodd" class="lg5xwxuqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:washing-machine-minimalistic-bold" /></template>
