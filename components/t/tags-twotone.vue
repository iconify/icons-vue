<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veq_qkvet.css';
import '../../css/i/i207xkr6i.css';
import '../../css/x/xf--gdc6m.css';
import '../../css/t/tfq-59bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="veq_qkvet"/><path class="i207xkr6i"/><path class="xf--gdc6m"/><path class="tfq-59bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:tags-twotone" /></template>
