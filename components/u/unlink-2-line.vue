<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2e_69o0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2e_69o0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unlink-2-line" /></template>
