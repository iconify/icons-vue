<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkblh9o1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lkblh9o1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:nuget" /></template>
