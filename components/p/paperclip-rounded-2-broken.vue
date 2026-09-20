<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0sxnixmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0sxnixmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-rounded-2-broken" /></template>
