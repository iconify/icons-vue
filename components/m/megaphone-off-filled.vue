<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f22uknsdn.css';
import '../../css/j/jpnuobtcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f22uknsdn"/><path class="jpnuobtcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:megaphone-off-filled" /></template>
