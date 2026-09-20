<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb-2zacbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb-2zacbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:telescope" /></template>
