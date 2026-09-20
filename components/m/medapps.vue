<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq6x1vb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pq6x1vb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:medapps" /></template>
