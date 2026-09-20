<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcm-6bb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gcm-6bb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-15-seconds-back-outline" /></template>
