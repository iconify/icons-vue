<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dspl9r1xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dspl9r1xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:paste" /></template>
