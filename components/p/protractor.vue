<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq85jqzsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tq85jqzsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:protractor" /></template>
