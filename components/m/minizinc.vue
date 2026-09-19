<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7w0g9z2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b7w0g9z2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:minizinc" /></template>
