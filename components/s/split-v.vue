<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogvxm-bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ogvxm-bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:split-v" /></template>
