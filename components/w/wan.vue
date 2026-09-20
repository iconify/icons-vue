<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm7t8jb2j.css';
import '../../css/a/agsh3e2_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm7t8jb2j"/><path class="agsh3e2_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wan" /></template>
