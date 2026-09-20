<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkdf4u1mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jkdf4u1mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:sales-return-outline" /></template>
