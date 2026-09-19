<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp_j_6pys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sp_j_6pys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:table-row-delete" /></template>
