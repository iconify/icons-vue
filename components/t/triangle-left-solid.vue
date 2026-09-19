<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndhusnblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ndhusnblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:triangle-left-solid" /></template>
