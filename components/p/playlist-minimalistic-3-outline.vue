<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcu_ujjgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lcu_ujjgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-3-outline" /></template>
