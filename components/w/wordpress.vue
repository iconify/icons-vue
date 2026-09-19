<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewyb3obxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ewyb3obxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:wordpress" /></template>
