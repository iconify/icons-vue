<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyu3op__j.css';
import '../../css/j/j37e0x93k.css';
import '../../css/q/qeni9rbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iyu3op__j"/><path class="j37e0x93k"/><path class="qeni9rbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:tag-twotone" /></template>
