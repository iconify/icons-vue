<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6p4c5b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6p4c5b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sun-solid" /></template>
