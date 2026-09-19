<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0udcsmcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="k0udcsmcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:sign-out" /></template>
