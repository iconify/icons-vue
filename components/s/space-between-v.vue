<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7ae3acat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7ae3acat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:space-between-v" /></template>
