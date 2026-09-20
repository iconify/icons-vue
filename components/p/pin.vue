<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a21x_b8wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="a21x_b8wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pin" /></template>
