<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8u6r351b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="v8u6r351b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:redo" /></template>
