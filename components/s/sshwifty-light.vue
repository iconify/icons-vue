<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf4cpj7cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cf4cpj7cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sshwifty-light" /></template>
