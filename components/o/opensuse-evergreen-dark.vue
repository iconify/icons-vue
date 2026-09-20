<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_rbdns9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_rbdns9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-evergreen-dark" /></template>
