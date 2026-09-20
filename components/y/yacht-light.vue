<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm-bt5bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fm-bt5bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yacht-light" /></template>
