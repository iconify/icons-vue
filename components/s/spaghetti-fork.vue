<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz_xxr-sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz_xxr-sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:spaghetti-fork" /></template>
