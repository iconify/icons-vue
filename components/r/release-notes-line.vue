<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7rfs572x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7rfs572x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:release-notes-line" /></template>
