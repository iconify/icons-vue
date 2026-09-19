<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhxtw9a1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhxtw9a1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wled" /></template>
