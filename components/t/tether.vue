<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiyj-2b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiyj-2b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tether" /></template>
