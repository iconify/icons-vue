<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlw-j7bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlw-j7bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sigma" /></template>
