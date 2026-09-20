<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj80bmbzo.css';
import '../../css/s/s4vpxwbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj80bmbzo"/><path class="s4vpxwbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:plan-light" /></template>
