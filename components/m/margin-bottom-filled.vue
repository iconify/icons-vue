<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj3p1-bpn.css';
import '../../css/e/exda4zbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj3p1-bpn"/><rect class="exda4zbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:margin-bottom-filled" /></template>
