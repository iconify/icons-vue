<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg6-z-39m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rg6-z-39m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-using-terminal-kiosk-with-shekel" /></template>
