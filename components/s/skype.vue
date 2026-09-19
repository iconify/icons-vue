<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycxm-968i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ycxm-968i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:skype" /></template>
