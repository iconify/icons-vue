<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkfbdfbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkfbdfbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-9-thin" /></template>
