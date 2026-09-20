<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttkmi5rnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttkmi5rnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:meta" /></template>
