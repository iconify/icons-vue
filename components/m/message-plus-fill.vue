<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykwmyg3xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykwmyg3xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-plus-fill" /></template>
