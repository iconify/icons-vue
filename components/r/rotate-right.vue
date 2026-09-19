<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m640nac0w.css';
import '../../css/b/bbh__hbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m640nac0w"/><path class="bbh__hbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:rotate-right" /></template>
