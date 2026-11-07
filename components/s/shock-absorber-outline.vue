<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mks2d9e3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mks2d9e3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shock-absorber-outline" /></template>
