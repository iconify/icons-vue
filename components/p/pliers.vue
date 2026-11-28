<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojm_wssze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojm_wssze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pliers" /></template>
