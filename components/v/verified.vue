<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qezsv0n_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qezsv0n_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:verified" /></template>
