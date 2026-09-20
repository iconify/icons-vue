<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw8y_lyiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zw8y_lyiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:steel-square-and-drafting-compass" /></template>
