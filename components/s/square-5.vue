<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dckm6kb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dckm6kb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:square-5" /></template>
