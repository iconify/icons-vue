<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6jmz7umj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e6jmz7umj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:slack-outline" /></template>
