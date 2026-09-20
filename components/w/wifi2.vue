<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9rw8nrxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c9rw8nrxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:wifi2" /></template>
