<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afl1-ubdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afl1-ubdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rectangle-solid" /></template>
