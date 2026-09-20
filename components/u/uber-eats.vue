<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txy-e_bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txy-e_bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:uber-eats" /></template>
