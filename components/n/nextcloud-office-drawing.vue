<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htmjl2bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="htmjl2bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-office-drawing" /></template>
