<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7fm4ccbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7fm4ccbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:swiss-franc-fill" /></template>
