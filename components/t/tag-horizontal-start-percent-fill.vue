<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeqmzy6dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aeqmzy6dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-start-percent-fill" /></template>
