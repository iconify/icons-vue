<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cckl8wolt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cckl8wolt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pill" /></template>
