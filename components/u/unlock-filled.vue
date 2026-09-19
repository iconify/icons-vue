<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd6ai1bvf.css';
import '../../css/y/yfgyogn5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="jd6ai1bvf"/><path clip-rule="evenodd" class="yfgyogn5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:unlock-filled" /></template>
