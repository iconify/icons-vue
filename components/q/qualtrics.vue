<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm6mt9v_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm6mt9v_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qualtrics" /></template>
