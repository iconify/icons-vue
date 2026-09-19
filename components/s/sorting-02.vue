<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvaf9bcdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvaf9bcdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sorting-02" /></template>
