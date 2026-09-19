<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud8zcybxg.css';
import '../../css/s/snzv8lbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ud8zcybxg"/><path class="snzv8lbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-file-storage" /></template>
