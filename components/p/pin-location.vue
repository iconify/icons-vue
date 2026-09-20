<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbk83jwqy.css';
import '../../css/c/cbhrk9bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbk83jwqy"/><path class="cbhrk9bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pin-location" /></template>
