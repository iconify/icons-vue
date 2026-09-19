<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wduwcxs0o.css';
import '../../css/s/srcmp7bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wduwcxs0o"/><path class="srcmp7bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:make-group" /></template>
