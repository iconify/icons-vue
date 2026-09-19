<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpi-wl9og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpi-wl9og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:volume-mute-filled" /></template>
