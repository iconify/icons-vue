<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6eec_-wn.css';
import '../../css/f/f-uh8goxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y6eec_-wn"/><path class="f-uh8goxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:trophy-twotone" /></template>
