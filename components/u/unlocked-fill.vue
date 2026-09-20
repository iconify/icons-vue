<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im2w-iywn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im2w-iywn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:unlocked-fill" /></template>
