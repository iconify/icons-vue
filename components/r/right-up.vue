<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3fqakbcn.css';
import '../../css/s/s3i81qbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u3fqakbcn"/><path class="s3i81qbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:right-up" /></template>
