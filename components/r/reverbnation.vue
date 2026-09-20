<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0t27pb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0t27pb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:reverbnation" /></template>
