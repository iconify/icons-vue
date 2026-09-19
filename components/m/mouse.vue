<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp5tixd2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="yp5tixd2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:mouse" /></template>
