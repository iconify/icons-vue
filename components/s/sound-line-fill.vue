<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq-olzb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq-olzb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sound-line-fill" /></template>
