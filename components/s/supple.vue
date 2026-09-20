<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd1o0wddx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qd1o0wddx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:supple" /></template>
