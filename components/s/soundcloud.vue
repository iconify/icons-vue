<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6oms2bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1280};
const content = `<path class="d6oms2bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:soundcloud" /></template>
