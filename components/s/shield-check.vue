<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0ei_2o1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l0ei_2o1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:shield-check" /></template>
