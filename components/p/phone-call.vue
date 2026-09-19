<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5b39c8fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5b39c8fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:phone-call" /></template>
