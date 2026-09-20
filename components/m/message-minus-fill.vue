<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp0p2xbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp0p2xbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-minus-fill" /></template>
