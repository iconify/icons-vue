<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku84tqx2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ku84tqx2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:monogram" /></template>
