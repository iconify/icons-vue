<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk9lgc8st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zk9lgc8st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:object-ungroup-outline" /></template>
