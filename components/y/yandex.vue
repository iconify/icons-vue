<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp9i4h5xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lp9i4h5xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:yandex" /></template>
