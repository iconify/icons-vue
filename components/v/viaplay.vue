<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tty_kn-fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tty_kn-fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:viaplay" /></template>
