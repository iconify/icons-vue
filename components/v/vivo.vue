<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4q0xobbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4q0xobbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vivo" /></template>
