<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km-w3zb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km-w3zb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shuttlecock-filled" /></template>
