<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tesv8obwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tesv8obwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:pfsense" /></template>
