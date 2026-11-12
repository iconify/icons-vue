<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emu_9rbiz.css';
import '../../css/a/a18sp8bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="emu_9rbiz"/><path class="a18sp8bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ultimate-certificate-manager-light" /></template>
