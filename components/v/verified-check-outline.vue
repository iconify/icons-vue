<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj2bkrcmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vj2bkrcmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:verified-check-outline" /></template>
