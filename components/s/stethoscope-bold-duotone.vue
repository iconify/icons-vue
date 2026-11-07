<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7ywjc5dv.css';
import '../../css/c/c5w0iq14v.css';
import '../../css/w/wvvwem2de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7ywjc5dv"/><path class="c5w0iq14v"/><path class="wvvwem2de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stethoscope-bold-duotone" /></template>
