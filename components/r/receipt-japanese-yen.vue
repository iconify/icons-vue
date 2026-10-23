<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7ya5vv3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ya5vv3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:receipt-japanese-yen" /></template>
