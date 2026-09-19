<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egwr0nbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="egwr0nbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:object-ungroup" /></template>
