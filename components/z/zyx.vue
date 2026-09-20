<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2r7a0-pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2r7a0-pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:zyx" /></template>
