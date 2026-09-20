<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz253gb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nz253gb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:skating-solid" /></template>
