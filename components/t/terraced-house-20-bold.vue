<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4-5bmdtc.css';
import '../../css/e/ei-x7jbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w4-5bmdtc"/><path class="ei-x7jbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:terraced-house-20-bold" /></template>
