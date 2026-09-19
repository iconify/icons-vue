<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv05x2o-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="wv05x2o-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:signal" /></template>
