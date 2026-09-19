<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aim5hzbvg.css';
import '../../css/e/e4iey6k0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aim5hzbvg"/><path class="e4iey6k0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:usb" /></template>
