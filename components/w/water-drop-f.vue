<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq_5smh8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="tq_5smh8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:water-drop-f" /></template>
