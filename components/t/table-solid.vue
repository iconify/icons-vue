<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezq_5gb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ezq_5gb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:table-solid" /></template>
