<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovx5lsblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovx5lsblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:teamviewer" /></template>
