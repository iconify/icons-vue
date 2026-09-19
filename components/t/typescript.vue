<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj7qqac8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="oj7qqac8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:typescript" /></template>
