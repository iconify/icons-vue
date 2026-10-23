<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfe17mbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfe17mbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scratch-blocks-filled" /></template>
