<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yth0o7dpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yth0o7dpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mirror2" /></template>
