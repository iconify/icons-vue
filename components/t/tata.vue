<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwtj_x3al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwtj_x3al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tata" /></template>
