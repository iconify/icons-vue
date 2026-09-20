<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v13-n1bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v13-n1bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:vlc-logo-block" /></template>
