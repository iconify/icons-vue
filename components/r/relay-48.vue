<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmp2mfr9i.css';
import '../../css/n/nsiiab0ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zmp2mfr9i"/><path class="nsiiab0ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:relay-48" /></template>
