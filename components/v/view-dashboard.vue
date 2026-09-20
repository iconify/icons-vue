<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxc-g272t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxc-g272t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:view-dashboard" /></template>
