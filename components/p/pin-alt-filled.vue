<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyhexrb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyhexrb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pin-alt-filled" /></template>
