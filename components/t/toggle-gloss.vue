<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn6qthh5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn6qthh5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:toggle-gloss" /></template>
