<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_a8u8b9v.css';
import '../../css/x/xwgviec-g.css';
import '../../css/b/btroue5fn.css';
import '../../css/o/ov69avbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n_a8u8b9v"/><path class="xwgviec-g"/><path class="btroue5fn"/><path class="ov69avbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:message-twotone" /></template>
