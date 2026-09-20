<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz6c57d1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xz6c57d1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield-x-filled" /></template>
