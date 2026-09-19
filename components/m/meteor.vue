<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5kcx5b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v5kcx5b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:meteor" /></template>
