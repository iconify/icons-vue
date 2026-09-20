<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdie0hb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mdie0hb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:plus" /></template>
