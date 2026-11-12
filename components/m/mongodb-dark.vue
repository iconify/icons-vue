<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yseymk-7a.css';
import '../../css/l/lt60qtbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yseymk-7a"/><path class="lt60qtbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mongodb-dark" /></template>
