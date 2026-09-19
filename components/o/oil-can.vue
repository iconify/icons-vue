<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/som-8wzkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="som-8wzkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:oil-can" /></template>
