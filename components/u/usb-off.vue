<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw617_bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qw617_bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:usb-off" /></template>
