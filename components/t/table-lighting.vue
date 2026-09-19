<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7eascc8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7eascc8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:table-lighting" /></template>
