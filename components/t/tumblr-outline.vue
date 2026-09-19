<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql-h63sot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ql-h63sot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:tumblr-outline" /></template>
