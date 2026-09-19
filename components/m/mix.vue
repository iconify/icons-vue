<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av8hnvbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="av8hnvbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:mix" /></template>
