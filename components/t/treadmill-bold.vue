<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6gx6-b_c.css';
import '../../css/u/ue3-gzbke.css';
import '../../css/y/yus7ucc0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6gx6-b_c"/><path clip-rule="evenodd" class="ue3-gzbke"/><path class="yus7ucc0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:treadmill-bold" /></template>
