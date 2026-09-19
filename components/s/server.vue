<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wobsqr1mq.css';
import '../../css/p/pw90w5qlp.css';
import '../../css/c/cwa6rzb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wobsqr1mq"/><path class="pw90w5qlp"/><path class="cwa6rzb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:server" /></template>
