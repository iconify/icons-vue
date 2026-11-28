<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynzuiobqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynzuiobqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:parenthesis-left-solid" /></template>
