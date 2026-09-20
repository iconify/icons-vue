<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-zbukb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m-zbukb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sliding-on-cliff" /></template>
