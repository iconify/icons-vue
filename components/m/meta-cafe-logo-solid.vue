<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lopm3jv9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lopm3jv9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:meta-cafe-logo-solid" /></template>
