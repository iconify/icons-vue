<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7k-jo7nm.css';
import '../../css/o/obxzrfd7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v7k-jo7nm"/><path class="obxzrfd7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:plus" /></template>
