<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmx8ijb7m.css';
import '../../css/i/ibya-7rop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zmx8ijb7m"/><path class="ibya-7rop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:namebadge" /></template>
