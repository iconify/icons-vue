<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erv4znb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="erv4znb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:smart-phone-fill" /></template>
