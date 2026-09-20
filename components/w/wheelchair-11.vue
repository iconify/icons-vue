<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9z8k-zja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="v9z8k-zja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:wheelchair-11" /></template>
