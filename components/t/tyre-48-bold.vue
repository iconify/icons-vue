<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moyoz5fkv.css';
import '../../css/e/e54qfbcyw.css';
import '../../css/o/ol4lf3bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="moyoz5fkv"/><path class="e54qfbcyw"/><path class="ol4lf3bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tyre-48-bold" /></template>
