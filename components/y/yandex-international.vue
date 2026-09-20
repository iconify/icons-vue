<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8knn_zqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v8knn_zqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:yandex-international" /></template>
