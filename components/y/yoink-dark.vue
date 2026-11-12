<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqk752b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xqk752b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yoink-dark" /></template>
