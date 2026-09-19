<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ontx3kbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ontx3kbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:usb" /></template>
