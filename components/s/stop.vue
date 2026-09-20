<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xutizuble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xutizuble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:stop" /></template>
