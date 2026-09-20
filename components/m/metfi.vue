<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpg0t8u7t.css';
import '../../css/c/ccmwlvz2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpg0t8u7t"/><path class="ccmwlvz2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:metfi" /></template>
