<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avdw4obvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="avdw4obvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pregnant-person" /></template>
