<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2kvcqbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2kvcqbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:unlock" /></template>
