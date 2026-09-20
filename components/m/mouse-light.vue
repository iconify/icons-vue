<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/d/d0h36taxe.css';
import '../../css/r/rmnh1fbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="d0h36taxe"/><path class="rmnh1fbii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:mouse-light" /></template>
