<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7lcc0bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="z7lcc0bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:qrcode" /></template>
