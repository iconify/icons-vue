<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeb6ks00l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xeb6ks00l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:satoshi-v1-filled" /></template>
