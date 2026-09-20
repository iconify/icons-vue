<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzzp8s6ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzzp8s6ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation" /></template>
