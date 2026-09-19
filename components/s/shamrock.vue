<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3bv18b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="k3bv18b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:shamrock" /></template>
