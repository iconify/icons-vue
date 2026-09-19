<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apfifgb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":704,"height":1024};
const content = `<path class="apfifgb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:usb" /></template>
