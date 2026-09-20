<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g45lxybwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g45lxybwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:submit-outline" /></template>
