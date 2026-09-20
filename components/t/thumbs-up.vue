<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfoc4ibca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="sfoc4ibca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:thumbs-up" /></template>
