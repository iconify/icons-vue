<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5f-44bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5f-44bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:scale-up" /></template>
