<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p305i0r_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p305i0r_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:waxp" /></template>
