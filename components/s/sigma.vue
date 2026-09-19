<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb8srpzjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sb8srpzjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:sigma" /></template>
