<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7i45dapy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7i45dapy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:text-align-end" /></template>
