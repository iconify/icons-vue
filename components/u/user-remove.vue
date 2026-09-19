<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9pbmhtyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9pbmhtyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:user-remove" /></template>
