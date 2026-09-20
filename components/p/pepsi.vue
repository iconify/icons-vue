<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvviu06qs.css';
import '../../css/w/wc7y-bc1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvviu06qs"/><path class="wc7y-bc1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pepsi" /></template>
