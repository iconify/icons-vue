<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj54vcbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj54vcbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:slash" /></template>
