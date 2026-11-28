<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyl6tnayy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyl6tnayy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:redo" /></template>
