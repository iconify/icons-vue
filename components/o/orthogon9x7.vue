<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luk64wbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="luk64wbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:orthogon9x7" /></template>
