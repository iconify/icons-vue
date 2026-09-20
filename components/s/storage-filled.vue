<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6ngtbcis.css';
import '../../css/k/k5o2fzblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c6ngtbcis"/><path clip-rule="evenodd" class="k5o2fzblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:storage-filled" /></template>
