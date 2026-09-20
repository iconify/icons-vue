<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic6slib8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic6slib8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tablet-solid" /></template>
