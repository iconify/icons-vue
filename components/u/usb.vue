<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2tf6pbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":464};
const content = `<path class="t2tf6pbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:usb" /></template>
