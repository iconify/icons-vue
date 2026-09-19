<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8g612boj.css';
import '../../css/q/qwz7habez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8g612boj st0"/><path class="qwz7habez st0"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:waffle-filled" /></template>
