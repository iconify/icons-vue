<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl3t-8q6w.css';
import '../../css/m/m6ntpracs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl3t-8q6w"/><path clip-rule="evenodd" class="m6ntpracs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-onedrive-logo-2-solid" /></template>
