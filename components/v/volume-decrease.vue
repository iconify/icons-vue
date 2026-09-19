<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awsw08b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="awsw08b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:volume-decrease" /></template>
