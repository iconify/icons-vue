<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkxewccxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="mkxewccxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-lock" /></template>
