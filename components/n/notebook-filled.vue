<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neh7qo-0n.css';
import '../../css/x/xs83kkb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="neh7qo-0n"/><path class="xs83kkb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:notebook-filled" /></template>
