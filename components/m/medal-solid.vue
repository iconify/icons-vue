<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewm7bp3sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewm7bp3sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:medal-solid" /></template>
