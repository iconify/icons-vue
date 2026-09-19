<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eebg1actu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eebg1actu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:pin-3" /></template>
