<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mij6dpb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mij6dpb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:restore-backup-pc" /></template>
