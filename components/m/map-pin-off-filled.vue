<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbehvzotf.css';
import '../../css/w/w-2f6ab8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zbehvzotf"/><path class="w-2f6ab8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pin-off-filled" /></template>
