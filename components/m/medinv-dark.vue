<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv5t23ldk.css';
import '../../css/f/fi8hk4b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vv5t23ldk"/><circle class="fi8hk4b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medinv-dark" /></template>
