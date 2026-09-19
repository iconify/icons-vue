<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a92_184ww.css';
import '../../css/m/miymqckna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a92_184ww"/><path class="miymqckna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:qr-code-filled" /></template>
