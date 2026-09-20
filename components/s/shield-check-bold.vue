<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6h5kl-3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f6h5kl-3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-check-bold" /></template>
