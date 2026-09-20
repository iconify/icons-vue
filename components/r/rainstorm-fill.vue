<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abgj25bzr.css';
import '../../css/a/almf4_bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abgj25bzr"/><path class="almf4_bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rainstorm-fill" /></template>
