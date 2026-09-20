<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p93get3aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p93get3aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:scan" /></template>
