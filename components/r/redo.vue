<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj29iu_gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sj29iu_gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:redo" /></template>
