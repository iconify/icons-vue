<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko7sfjdbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ko7sfjdbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:pingchat-logo-solid" /></template>
