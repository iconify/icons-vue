<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx3490c6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mx3490c6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:vpn-shield-bold" /></template>
