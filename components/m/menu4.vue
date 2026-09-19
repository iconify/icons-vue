<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-x8h-psw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":16};
const content = `<path class="f-x8h-psw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:menu4" /></template>
