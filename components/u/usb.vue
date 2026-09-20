<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8fddtb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b8fddtb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:usb" /></template>
