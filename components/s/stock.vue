<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idqb9kbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idqb9kbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:stock" /></template>
