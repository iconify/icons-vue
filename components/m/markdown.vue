<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpp8vfq_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpp8vfq_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:markdown" /></template>
