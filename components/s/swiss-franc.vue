<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnszo_bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnszo_bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swiss-franc" /></template>
