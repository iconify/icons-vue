<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuvdbbbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuvdbbbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:television" /></template>
