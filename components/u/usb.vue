<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loioe4qmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loioe4qmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:usb" /></template>
