<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t32frmb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t32frmb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:mute" /></template>
