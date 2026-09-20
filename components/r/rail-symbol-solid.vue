<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_au6tt1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_au6tt1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rail-symbol-solid" /></template>
