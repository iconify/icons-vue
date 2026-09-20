<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qix4teb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qix4teb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:surface-top-filled" /></template>
