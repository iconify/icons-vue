<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjna77bsx.css';
import '../../css/z/z02gnab-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjna77bsx"/><path clip-rule="evenodd" class="z02gnab-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shrimp-filled" /></template>
