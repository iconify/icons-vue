<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4xyx_bsy.css';
import '../../css/t/tkzh8yb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p4xyx_bsy"/><path class="tkzh8yb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-cloudy" /></template>
