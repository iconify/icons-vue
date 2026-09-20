<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrfxpszrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrfxpszrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:sign-badge-badge-1" /></template>
