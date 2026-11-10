<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlv13-epe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlv13-epe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:omicron" /></template>
