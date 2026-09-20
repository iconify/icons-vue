<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q06-nox-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q06-nox-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:shazam-logo-block" /></template>
