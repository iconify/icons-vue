<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf4c34b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf4c34b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wifi-extender" /></template>
