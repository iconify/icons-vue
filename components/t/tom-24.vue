<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0pl5fbue.css';
import '../../css/h/h-67_2kzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0pl5fbue"/><path clip-rule="evenodd" class="h-67_2kzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:tom-24" /></template>
