<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygaj_8b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygaj_8b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:volume-control" /></template>
