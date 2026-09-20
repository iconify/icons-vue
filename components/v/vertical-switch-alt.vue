<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zucdqebvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zucdqebvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:vertical-switch-alt" /></template>
