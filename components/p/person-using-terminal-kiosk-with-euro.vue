<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_ne7b7zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f_ne7b7zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-using-terminal-kiosk-with-euro" /></template>
