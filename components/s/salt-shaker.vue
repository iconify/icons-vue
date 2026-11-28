<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6ou59bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6ou59bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:salt-shaker" /></template>
