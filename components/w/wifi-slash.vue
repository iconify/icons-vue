<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyqpd9b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="cyqpd9b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:wifi-slash" /></template>
