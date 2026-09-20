<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkieu6b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bkieu6b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-using-terminal-kiosk" /></template>
