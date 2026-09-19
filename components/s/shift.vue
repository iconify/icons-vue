<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdgvuia_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdgvuia_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:shift" /></template>
