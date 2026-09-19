<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii7we8yak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ii7we8yak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:music-off-filled" /></template>
