<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1p808bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="b1p808bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:map-marked-alt" /></template>
