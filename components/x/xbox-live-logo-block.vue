<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5zt5obnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g5zt5obnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:xbox-live-logo-block" /></template>
