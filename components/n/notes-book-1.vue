<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3hyvhbfs.css';
import '../../css/s/swin4bcne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3hyvhbfs"/><path class="swin4bcne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:notes-book-1" /></template>
