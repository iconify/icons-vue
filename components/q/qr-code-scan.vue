<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyzglvbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyzglvbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:qr-code-scan" /></template>
