<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plv78-b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="plv78-b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:table-row-delete" /></template>
