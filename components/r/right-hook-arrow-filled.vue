<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr4grdbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fr4grdbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-hook-arrow-filled" /></template>
