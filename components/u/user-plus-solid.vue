<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4al6hb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p4al6hb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:user-plus-solid" /></template>
