<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f298x6yqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f298x6yqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mailbox-outline" /></template>
