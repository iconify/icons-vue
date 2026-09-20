<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it4il9byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it4il9byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tidb" /></template>
