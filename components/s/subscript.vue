<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3b13z1gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3b13z1gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:subscript" /></template>
