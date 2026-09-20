<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-6-22fzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="x-6-22fzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:paste" /></template>
