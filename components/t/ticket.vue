<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw0upqbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qw0upqbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ticket" /></template>
