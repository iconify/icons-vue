<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8b-5obnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8b-5obnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:washing-machine-alert" /></template>
