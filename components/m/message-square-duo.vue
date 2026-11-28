<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjd2x0bfl.css';
import '../../css/j/jjkgeh70e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjd2x0bfl secondary"/><path class="jjkgeh70e primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-duo" /></template>
