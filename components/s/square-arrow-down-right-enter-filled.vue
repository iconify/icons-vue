<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3kj2qixg.css';
import '../../css/w/wygmz5bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3kj2qixg"/><path class="wygmz5bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-down-right-enter-filled" /></template>
