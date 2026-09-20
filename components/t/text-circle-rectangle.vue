<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8p397xka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k8p397xka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:text-circle-rectangle" /></template>
