<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkfh-wbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkfh-wbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:settings-adjust-vertical-filled" /></template>
