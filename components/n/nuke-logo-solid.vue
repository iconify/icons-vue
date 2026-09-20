<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aehpp3bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aehpp3bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:nuke-logo-solid" /></template>
