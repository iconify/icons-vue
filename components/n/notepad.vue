<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b18u8acww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="b18u8acww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:notepad" /></template>
