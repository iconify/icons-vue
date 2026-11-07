<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc_x2tbuz.css';
import '../../css/m/mms9xzmvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc_x2tbuz"/><path class="mms9xzmvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sticker-circle-bold" /></template>
