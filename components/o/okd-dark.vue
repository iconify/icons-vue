<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itr6d0bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="itr6d0bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:okd-dark" /></template>
