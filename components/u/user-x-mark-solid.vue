<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ims0hnb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ims0hnb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:user-x-mark-solid" /></template>
