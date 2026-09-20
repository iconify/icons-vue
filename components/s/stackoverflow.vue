<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbbvttb9i.css';
import '../../css/w/we1tctbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbbvttb9i"/><path class="we1tctbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:stackoverflow" /></template>
