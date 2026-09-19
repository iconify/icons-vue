<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkzpn6n4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dkzpn6n4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:wolfram-language" /></template>
