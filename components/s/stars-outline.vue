<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsz2wpbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rsz2wpbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stars-outline" /></template>
