<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzap-88ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzap-88ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-barcode-sharp" /></template>
