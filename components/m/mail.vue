<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdf4szbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cdf4szbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:mail" /></template>
