<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyc7oevht.css';
import '../../css/g/g-rrphyqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyc7oevht"/><path clip-rule="evenodd" class="g-rrphyqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wallet-outline" /></template>
