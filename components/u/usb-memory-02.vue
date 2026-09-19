<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e31ph7fnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e31ph7fnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:usb-memory-02" /></template>
