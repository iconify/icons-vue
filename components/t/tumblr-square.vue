<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-296b9zl.css';
import '../../css/u/u0j55db0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-296b9zl"/><path class="u0j55db0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:tumblr-square" /></template>
