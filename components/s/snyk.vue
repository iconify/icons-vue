<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx5jx9gaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lx5jx9gaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:snyk" /></template>
