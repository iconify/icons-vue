<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_zk3-m4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k_zk3-m4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vyper" /></template>
