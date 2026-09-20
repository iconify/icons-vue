<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfu2lbbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qfu2lbbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:playstation-light" /></template>
