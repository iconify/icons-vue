<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gntq4wbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gntq4wbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:microscope" /></template>
