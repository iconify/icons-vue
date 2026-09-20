<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfydpnbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfydpnbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:plus-one" /></template>
