<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r69w_s5qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r69w_s5qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tunnel-fill" /></template>
