<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac7p6yblo.css';
import '../../css/n/njy6bmz6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ac7p6yblo"/><path class="njy6bmz6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wattmeter-48" /></template>
