<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw4h6c1fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hw4h6c1fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:users-20-bold" /></template>
