<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4-2-ubeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="n4-2-ubeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-x" /></template>
