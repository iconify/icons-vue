<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngo9cq6cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ngo9cq6cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:marketo" /></template>
