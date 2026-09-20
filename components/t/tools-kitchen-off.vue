<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7xeb6bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7xeb6bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tools-kitchen-off" /></template>
