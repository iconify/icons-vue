<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6y4q0buk.css';
import '../../css/y/ykgt55trn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f6y4q0buk"/><path class="ykgt55trn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rolling-pin-48-bold" /></template>
