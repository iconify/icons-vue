<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1c0irbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1c0irbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:music-note-04" /></template>
