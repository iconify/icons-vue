<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_3cypb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="w_3cypb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:town-hall-11" /></template>
