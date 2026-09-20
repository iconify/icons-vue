<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx0db3bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx0db3bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pfsense" /></template>
