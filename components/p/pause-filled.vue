<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9_pisd2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9_pisd2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:pause-filled" /></template>
