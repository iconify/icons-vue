<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylaicorwm.css';
import '../../css/s/su7a0euxn.css';
import '../../css/n/np4ropmkg.css';
import '../../css/b/bg3wu7bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ylaicorwm"/><path class="su7a0euxn"/><path class="np4ropmkg"/><path class="bg3wu7bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:usb-48-bold" /></template>
