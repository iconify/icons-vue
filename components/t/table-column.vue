<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgmrll23v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgmrll23v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-column" /></template>
