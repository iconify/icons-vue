<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk706fomp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk706fomp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:video-edit-magic-wand-bold" /></template>
