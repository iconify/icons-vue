<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq2talg6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq2talg6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pants" /></template>
