<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0j2j0bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0j2j0bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mic-off-02" /></template>
