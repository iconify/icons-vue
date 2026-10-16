<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5wxjvy9k.css';
import '../../css/m/mo8aawb0e.css';
import '../../css/l/luei4dbch.css';
import '../../css/d/d8u9wobbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":87.5,"height":100};
const content = `<path class="k5wxjvy9k"/><path class="mo8aawb0e"/><path class="luei4dbch"/><path class="d8u9wobbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:semaphore-ui" /></template>
