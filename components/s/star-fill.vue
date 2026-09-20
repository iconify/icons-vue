<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iql4axbme.css';
import '../../css/n/nd6bc6b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGwDJxaeOQ)"><path class="iql4axbme"/></g><defs><clipPath id="SVGwDJxaeOQ"><path class="nd6bc6b-x"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:star-fill" /></template>
