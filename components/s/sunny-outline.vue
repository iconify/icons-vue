<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzoe01kfd.css';
import '../../css/q/qdd1rtb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pzoe01kfd"/><circle class="qdd1rtb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:sunny-outline" /></template>
