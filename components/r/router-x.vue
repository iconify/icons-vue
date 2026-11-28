<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_4q0l3ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_4q0l3ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:router-x" /></template>
