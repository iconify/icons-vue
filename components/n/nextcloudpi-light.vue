<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akmyxebxj.css';
import '../../css/z/zf1qckbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="akmyxebxj"/><path clip-rule="evenodd" class="zf1qckbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloudpi-light" /></template>
