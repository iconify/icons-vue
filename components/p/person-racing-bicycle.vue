<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b69k8vrkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b69k8vrkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-racing-bicycle" /></template>
