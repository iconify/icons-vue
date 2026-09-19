<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp4u1ql3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4u1ql3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:qr-code-outline" /></template>
