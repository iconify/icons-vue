<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0ikg4bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n0ikg4bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mobile-phone-camera-solid" /></template>
