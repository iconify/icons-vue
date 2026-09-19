<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcfxtrb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bcfxtrb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:test-ruby" /></template>
