<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spdlrf7lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="spdlrf7lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:school-bus-side-solid" /></template>
