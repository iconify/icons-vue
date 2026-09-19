<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va9ht3buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va9ht3buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wave-square" /></template>
