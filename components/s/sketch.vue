<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knsr0lbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="knsr0lbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:sketch" /></template>
