<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub9sfq3xt.css';
import '../../css/m/mkx79kbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub9sfq3xt"/><path class="mkx79kbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pencil-writing" /></template>
