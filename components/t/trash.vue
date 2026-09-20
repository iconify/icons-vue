<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6gtnxgyh.css';
import '../../css/g/gsv3t-buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z6gtnxgyh"/><path class="gsv3t-buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:trash" /></template>
