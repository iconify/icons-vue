<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-qlm7bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c-qlm7bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:wordpress-alt" /></template>
