<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stp3e0b8u.css';
import '../../css/j/jmadxbr5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stp3e0b8u"/><path class="jmadxbr5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rdd" /></template>
