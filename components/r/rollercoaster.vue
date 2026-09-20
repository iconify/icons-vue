<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h23tj7btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h23tj7btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rollercoaster" /></template>
