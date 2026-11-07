<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gflkqcblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gflkqcblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-bold-broken" /></template>
