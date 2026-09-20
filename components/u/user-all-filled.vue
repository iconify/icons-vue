<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzvhlcc-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lzvhlcc-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:user-all-filled" /></template>
