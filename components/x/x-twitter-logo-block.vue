<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwyht6g7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lwyht6g7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:x-twitter-logo-block" /></template>
