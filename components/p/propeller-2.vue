<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grvocubmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="grvocubmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:propeller-2" /></template>
