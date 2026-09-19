<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vap8vfq9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="vap8vfq9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:refresh-alt" /></template>
