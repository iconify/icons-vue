<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yijcz5bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yijcz5bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tag" /></template>
