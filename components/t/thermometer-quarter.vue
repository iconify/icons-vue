<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bapu0m6tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bapu0m6tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:thermometer-quarter" /></template>
