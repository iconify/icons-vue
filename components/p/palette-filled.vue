<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r59jsbmuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r59jsbmuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:palette-filled" /></template>
