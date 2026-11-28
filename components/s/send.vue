<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w974s6-xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w974s6-xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:send" /></template>
