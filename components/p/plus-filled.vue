<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_dochtfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z_dochtfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:plus-filled" /></template>
