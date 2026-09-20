<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy78obcut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy78obcut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sunset-2-filled" /></template>
