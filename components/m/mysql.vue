<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjv0iobtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wjv0iobtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:mysql" /></template>
