<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp8z5tbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yp8z5tbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-using-terminal-kiosk-with-dollar" /></template>
