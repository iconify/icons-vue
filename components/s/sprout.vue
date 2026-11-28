<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doie_cbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doie_cbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sprout" /></template>
