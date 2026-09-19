<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxbl4ccqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxbl4ccqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:qr-code-01" /></template>
