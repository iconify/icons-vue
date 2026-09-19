<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oui1n645i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="oui1n645i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:themeco" /></template>
