<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6rx90b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6rx90b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:umbraco" /></template>
