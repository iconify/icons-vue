<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8_kujybw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8_kujybw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:smoke-alarm-filled" /></template>
