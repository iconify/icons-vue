<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdh4pbbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdh4pbbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-95-small" /></template>
