<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe5gnfbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe5gnfbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:trending-down-sharp-fill" /></template>
