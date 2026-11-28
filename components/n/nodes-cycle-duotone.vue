<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbytk1gwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbytk1gwj primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:nodes-cycle-duotone" /></template>
