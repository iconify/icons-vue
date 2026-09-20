<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmvuqobtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qmvuqobtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:square-outline" /></template>
