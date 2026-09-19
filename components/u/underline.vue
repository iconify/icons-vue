<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1u1swbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="t1u1swbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:underline" /></template>
