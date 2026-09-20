<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss_8qxzuj.css';
import '../../css/o/od1iqpboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ss_8qxzuj"/><path class="od1iqpboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:outline" /></template>
