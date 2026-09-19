<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db_fracjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db_fracjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:symptoms-cold-fever" /></template>
