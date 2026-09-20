<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9u5hk_ay.css';
import '../../css/e/eu62npp2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9u5hk_ay"/><path class="eu62npp2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tv-filled" /></template>
