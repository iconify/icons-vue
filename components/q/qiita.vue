<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njbyc1zgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="njbyc1zgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:qiita" /></template>
