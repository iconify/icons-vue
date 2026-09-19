<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nblah3f0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nblah3f0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:more-02" /></template>
