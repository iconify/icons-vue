<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxa6clbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="fxa6clbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:times" /></template>
