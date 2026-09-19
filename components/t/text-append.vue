<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko-5hi22e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ko-5hi22e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-append" /></template>
