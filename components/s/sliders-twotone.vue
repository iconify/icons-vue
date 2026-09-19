<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaa10iz8w.css';
import '../../css/i/is07s5r9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iaa10iz8w"/><path class="is07s5r9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:sliders-twotone" /></template>
