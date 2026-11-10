<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwy545bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwy545bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-heading-four" /></template>
