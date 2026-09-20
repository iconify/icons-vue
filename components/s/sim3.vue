<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw0kxo5rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gw0kxo5rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sim3" /></template>
