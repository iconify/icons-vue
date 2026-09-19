<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cya1rgi2m.css';
import '../../css/s/s7ta3byys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="cya1rgi2m"/><path class="s7ta3byys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wifi-off" /></template>
