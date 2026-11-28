<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbklvmb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pbklvmb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:whistle-thin" /></template>
