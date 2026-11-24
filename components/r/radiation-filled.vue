<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3eh531-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3eh531-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:radiation-filled" /></template>
