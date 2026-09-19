<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebce-tb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebce-tb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:maximize-01" /></template>
