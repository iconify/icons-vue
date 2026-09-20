<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i98kxfuyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i98kxfuyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:traffic-filled" /></template>
