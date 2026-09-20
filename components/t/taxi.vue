<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg1wvhb_r.css';
import '../../css/j/j-6v1gb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jg1wvhb_r"/><path class="j-6v1gb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:taxi" /></template>
