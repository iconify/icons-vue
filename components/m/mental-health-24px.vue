<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8osuqbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l8osuqbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mental-health-24px" /></template>
