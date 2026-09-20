<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk16tac8i.css';
import '../../css/h/hnr6sxbeb.css';
import '../../css/i/i9ou5abuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vk16tac8i"/><path class="hnr6sxbeb"/><path class="i9ou5abuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onlyoffice-dark" /></template>
