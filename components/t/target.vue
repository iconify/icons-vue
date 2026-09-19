<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8f5sybzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f8f5sybzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:target" /></template>
