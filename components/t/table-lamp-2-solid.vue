<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krazb_jdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="krazb_jdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:table-lamp-2-solid" /></template>
