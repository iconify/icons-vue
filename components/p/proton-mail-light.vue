<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq3zh6b0i.css';
import '../../css/f/f8da0bkqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oq3zh6b0i"/><path class="f8da0bkqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-mail-light" /></template>
