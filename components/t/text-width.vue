<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgqlzrbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":24};
const content = `<path class="zgqlzrbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:text-width" /></template>
