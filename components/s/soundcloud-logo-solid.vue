<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqa6zxbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yqa6zxbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:soundcloud-logo-solid" /></template>
