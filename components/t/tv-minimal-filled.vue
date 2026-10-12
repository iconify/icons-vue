<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu531kbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu531kbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tv-minimal-filled" /></template>
