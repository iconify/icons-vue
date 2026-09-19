<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4jbpvzyd.css';
import '../../css/t/t6ftoevsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c4jbpvzyd"/><path class="t6ftoevsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pushpin-twotone" /></template>
