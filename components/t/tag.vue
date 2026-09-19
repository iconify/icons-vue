<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj45sdbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lj45sdbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tag" /></template>
