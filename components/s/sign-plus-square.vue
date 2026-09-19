<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpn4uz37n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpn4uz37n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-square" /></template>
