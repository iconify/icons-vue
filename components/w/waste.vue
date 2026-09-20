<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djko6_bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="djko6_bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:waste" /></template>
