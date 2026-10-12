<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6c5cdb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6c5cdb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-split-horizontal-filled" /></template>
