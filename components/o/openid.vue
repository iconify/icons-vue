<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j58xd_syr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j58xd_syr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:openid" /></template>
