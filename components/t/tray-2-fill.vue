<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cazy9sb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cazy9sb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tray-2-fill" /></template>
