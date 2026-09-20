<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de6tnr8sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="de6tnr8sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:volume-1-solid" /></template>
