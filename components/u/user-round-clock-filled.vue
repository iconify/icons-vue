<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mscisxwkl.css';
import '../../css/g/gajart-oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mscisxwkl"/><path class="gajart-oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-clock-filled" /></template>
