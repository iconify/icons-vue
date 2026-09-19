<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiqd9zd2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qiqd9zd2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:terminal" /></template>
