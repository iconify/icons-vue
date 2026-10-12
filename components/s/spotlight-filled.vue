<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqwyvib6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqwyvib6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:spotlight-filled" /></template>
