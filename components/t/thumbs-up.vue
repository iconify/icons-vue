<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaj23_bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qaj23_bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:thumbs-up" /></template>
