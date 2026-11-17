<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba8ce4b4q.css';
import '../../css/t/t31j6x04d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8ce4b4q"/><path class="t31j6x04d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-up-enter-filled" /></template>
