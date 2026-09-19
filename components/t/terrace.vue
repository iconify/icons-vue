<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnk0dbcou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnk0dbcou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:terrace" /></template>
