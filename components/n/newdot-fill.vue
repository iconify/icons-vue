<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdw94qbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdw94qbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:newdot-fill" /></template>
