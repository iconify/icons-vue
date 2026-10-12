<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox69vdbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox69vdbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-pointer-filled" /></template>
