<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk1lweb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="qk1lweb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:wheelchair" /></template>
