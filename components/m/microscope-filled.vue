<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze41jub0z.css';
import '../../css/q/qr98xybve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze41jub0z"/><path class="qr98xybve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microscope-filled" /></template>
