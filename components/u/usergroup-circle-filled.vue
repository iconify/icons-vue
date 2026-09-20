<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jliwh3b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jliwh3b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:usergroup-circle-filled" /></template>
