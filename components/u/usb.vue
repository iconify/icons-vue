<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nitc4wk5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nitc4wk5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:usb" /></template>
