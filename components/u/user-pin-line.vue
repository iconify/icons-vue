<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozh610-un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozh610-un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-pin-line" /></template>
