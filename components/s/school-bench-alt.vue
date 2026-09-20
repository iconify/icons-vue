<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqhi0svru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gqhi0svru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:school-bench-alt" /></template>
