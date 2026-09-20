<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owjnpnrlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="owjnpnrlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:stumble-upon-2ing-logo-solid" /></template>
