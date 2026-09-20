<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfd4evfpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfd4evfpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-left-broken" /></template>
