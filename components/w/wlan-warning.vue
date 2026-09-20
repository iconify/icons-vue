<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk9_w01ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bk9_w01ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:wlan-warning" /></template>
