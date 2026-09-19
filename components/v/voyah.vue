<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9kjepb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9kjepb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:voyah" /></template>
