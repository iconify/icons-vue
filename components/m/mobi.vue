<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmzcyxbor.css';
import '../../css/c/cdw1yt0dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmzcyxbor"/><path class="cdw1yt0dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mobi" /></template>
