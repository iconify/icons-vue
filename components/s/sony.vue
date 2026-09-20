<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok6tfckgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok6tfckgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sony" /></template>
