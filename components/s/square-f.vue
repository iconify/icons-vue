<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em-cw7emi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="em-cw7emi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:square-f" /></template>
