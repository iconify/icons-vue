<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7ah-93km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7ah-93km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-socket-cn" /></template>
