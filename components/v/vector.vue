<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwqm4xb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwqm4xb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vector" /></template>
