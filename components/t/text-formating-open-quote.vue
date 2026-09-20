<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmvwjgs2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wmvwjgs2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:text-formating-open-quote" /></template>
