<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvtpd8bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvtpd8bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-pen-filled" /></template>
