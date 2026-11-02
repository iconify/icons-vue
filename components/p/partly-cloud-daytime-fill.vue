<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhvnvmb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhvnvmb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:partly-cloud-daytime-fill" /></template>
