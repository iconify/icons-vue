<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exn257bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exn257bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:play-solid" /></template>
