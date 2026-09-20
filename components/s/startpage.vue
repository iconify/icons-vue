<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi915ebew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi915ebew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:startpage" /></template>
