<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg8y9i1fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":472};
const content = `<path class="jg8y9i1fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:sun" /></template>
