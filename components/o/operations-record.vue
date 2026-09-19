<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evzzowain.css';
import '../../css/p/p0vee9bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="evzzowain"/><path class="p0vee9bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:operations-record" /></template>
