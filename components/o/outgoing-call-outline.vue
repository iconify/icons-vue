<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtoomg9sp.css';
import '../../css/a/accmcc7bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xtoomg9sp"/><path class="accmcc7bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:outgoing-call-outline" /></template>
