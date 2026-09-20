<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzr1hwbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzr1hwbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:teamspeak" /></template>
