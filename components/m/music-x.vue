<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tygr07bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tygr07bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-x" /></template>
