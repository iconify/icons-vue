<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd-3o55-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sd-3o55-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:text-input-filled" /></template>
