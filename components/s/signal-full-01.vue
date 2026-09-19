<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnawqtehn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnawqtehn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:signal-full-01" /></template>
