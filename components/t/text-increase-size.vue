<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjw6ldbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjw6ldbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-increase-size" /></template>
