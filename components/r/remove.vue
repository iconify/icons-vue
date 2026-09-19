<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu8eogszi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="qu8eogszi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:remove" /></template>
