<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2h7nfjar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2h7nfjar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:speedboat-filled" /></template>
