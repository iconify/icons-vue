<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_cbxqb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="k_cbxqb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:viking" /></template>
