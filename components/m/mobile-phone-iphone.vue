<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmx67wbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmx67wbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mobile-phone-iphone" /></template>
