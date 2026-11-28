<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow2oqr99c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow2oqr99c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tshirt-plus" /></template>
