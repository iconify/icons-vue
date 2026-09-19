<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abefcjbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="abefcjbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:navicon" /></template>
