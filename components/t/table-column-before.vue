<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdq6b-e_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="mdq6b-e_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:table-column-before" /></template>
