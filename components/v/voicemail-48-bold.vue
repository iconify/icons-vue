<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpgircbhz.css';
import '../../css/o/ouirlxbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gpgircbhz"/><path class="ouirlxbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voicemail-48-bold" /></template>
