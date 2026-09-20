<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czi0srbta.css';
import '../../css/c/cdpzc0bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czi0srbta"/><path class="cdpzc0bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:users-crown" /></template>
