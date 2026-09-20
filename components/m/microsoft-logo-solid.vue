<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs3wtqbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bs3wtqbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-logo-solid" /></template>
