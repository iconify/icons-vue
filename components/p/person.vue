<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk3_bpbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nk3_bpbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:person" /></template>
