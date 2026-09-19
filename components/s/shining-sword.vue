<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azvuicc1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="azvuicc1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shining-sword" /></template>
