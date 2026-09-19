<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahe5khbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahe5khbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wifi-02" /></template>
