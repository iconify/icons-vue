<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3o3ldbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z3o3ldbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:medical-sharp" /></template>
