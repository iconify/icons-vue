<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atw-gidih.css';
import '../../css/a/a8m-_-bks.css';
import '../../css/j/juspnkb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="atw-gidih"/><path class="a8m-_-bks"/><path class="juspnkb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:rest-twotone" /></template>
