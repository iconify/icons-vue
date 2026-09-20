<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7kf9dwlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7kf9dwlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-minus" /></template>
