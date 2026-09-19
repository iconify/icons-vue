<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u27b7vd_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u27b7vd_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:stop-circle-fill" /></template>
