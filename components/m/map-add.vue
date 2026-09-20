<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch04xou5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch04xou5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-add" /></template>
