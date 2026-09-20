<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aomehwb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aomehwb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:subscription-list" /></template>
