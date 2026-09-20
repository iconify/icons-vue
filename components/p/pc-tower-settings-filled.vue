<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz2j7vb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wz2j7vb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pc-tower-settings-filled" /></template>
