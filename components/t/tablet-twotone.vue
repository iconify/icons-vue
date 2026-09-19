<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q712rm2xz.css';
import '../../css/a/aw76ujlyo.css';
import '../../css/w/w68m2kb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q712rm2xz"/><path class="aw76ujlyo"/><path class="w68m2kb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:tablet-twotone" /></template>
