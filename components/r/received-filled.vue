<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbg8k2e_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbg8k2e_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:received-filled" /></template>
