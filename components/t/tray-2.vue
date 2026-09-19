<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewppc3bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ewppc3bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tray-2" /></template>
