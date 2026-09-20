<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssk1sbbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ssk1sbbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:save-as-filled" /></template>
