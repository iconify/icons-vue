<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfxbh8bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zfxbh8bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-alt-arrow-up-bold" /></template>
