<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_f5fmb5w.css';
import '../../css/d/dgp7bubto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_f5fmb5w"/><path class="dgp7bubto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:window-restore-solid" /></template>
