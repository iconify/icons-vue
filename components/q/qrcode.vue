<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djat35b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="djat35b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:qrcode" /></template>
