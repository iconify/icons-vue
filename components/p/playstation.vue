<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lie2npblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="lie2npblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:playstation" /></template>
