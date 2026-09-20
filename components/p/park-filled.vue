<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bumd6o66x.css';
import '../../css/i/ix2n_eb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bumd6o66x"/><path clip-rule="evenodd" class="ix2n_eb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:park-filled" /></template>
