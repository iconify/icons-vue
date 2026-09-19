<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk91yiz0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk91yiz0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-cells-filled" /></template>
