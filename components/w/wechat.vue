<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_i598bje.css';
import '../../css/z/zevd0dbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_i598bje"/><path class="zevd0dbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:wechat" /></template>
