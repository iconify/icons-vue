<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnr1s3bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="rnr1s3bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:text-paragraph" /></template>
