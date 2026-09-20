<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohqfqp6at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohqfqp6at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:perl" /></template>
