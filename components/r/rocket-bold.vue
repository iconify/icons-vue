<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1ywg7b9f.css';
import '../../css/r/rcgsjubiv.css';
import '../../css/y/ym8wn7bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1ywg7b9f"/><path class="rcgsjubiv"/><path clip-rule="evenodd" class="ym8wn7bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rocket-bold" /></template>
