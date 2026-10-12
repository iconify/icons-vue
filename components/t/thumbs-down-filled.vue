<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oslr7smei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oslr7smei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:thumbs-down-filled" /></template>
