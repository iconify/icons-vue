<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns_c3jf9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns_c3jf9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-xbox-gamepad-off" /></template>
