<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_-5f0bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_-5f0bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mobile-signal-two" /></template>
