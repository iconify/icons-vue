<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q86b8g1uw.css';
import '../../css/x/x5qh69bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q86b8g1uw"/><path clip-rule="evenodd" class="x5qh69bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:soap-dispenser-droplet-filled" /></template>
