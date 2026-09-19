<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scsv6ubbs.css';
import '../../css/n/nxv1jnq8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="scsv6ubbs"/><path class="nxv1jnq8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:reply-all" /></template>
