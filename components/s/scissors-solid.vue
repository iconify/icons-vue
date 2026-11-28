<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oku_46b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oku_46b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scissors-solid" /></template>
