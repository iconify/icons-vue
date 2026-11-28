<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plzz2p7cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plzz2p7cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:usb-x" /></template>
