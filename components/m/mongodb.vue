<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzwts81us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":1024};
const content = `<path class="tzwts81us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mongodb" /></template>
