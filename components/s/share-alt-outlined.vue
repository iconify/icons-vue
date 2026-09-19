<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0wlenb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h0wlenb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:share-alt-outlined" /></template>
