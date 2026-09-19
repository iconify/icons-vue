<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr7eoibfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sr7eoibfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:printer-solid" /></template>
