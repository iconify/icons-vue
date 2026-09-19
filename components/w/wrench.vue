<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myuy8im6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="myuy8im6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:wrench" /></template>
