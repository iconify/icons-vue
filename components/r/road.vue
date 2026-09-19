<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhko6i8qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="nhko6i8qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:road" /></template>
