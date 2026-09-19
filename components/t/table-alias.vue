<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqc3tesvm.css';
import '../../css/s/s-cmdjj4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aqc3tesvm"/><path class="s-cmdjj4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:table-alias" /></template>
