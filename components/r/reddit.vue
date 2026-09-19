<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9s_yp61w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9s_yp61w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:reddit" /></template>
