<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heq9tpbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="heq9tpbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:undo-gloss" /></template>
