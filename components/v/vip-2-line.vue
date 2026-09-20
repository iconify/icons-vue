<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myq_lyb9f.css';
import '../../css/k/kkjzqzj2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myq_lyb9f"/><path class="kkjzqzj2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vip-2-line" /></template>
