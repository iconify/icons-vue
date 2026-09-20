<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa7_ribhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa7_ribhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:pause" /></template>
