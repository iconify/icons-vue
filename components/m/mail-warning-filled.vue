<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiwzlsbsz.css';
import '../../css/z/zz89phbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiwzlsbsz"/><path class="zz89phbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-warning-filled" /></template>
